<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnbnafbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnbnafbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gender-female-solid" /></template>
