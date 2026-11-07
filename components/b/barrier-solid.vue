<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqms-5g7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqms-5g7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:barrier-solid" /></template>
