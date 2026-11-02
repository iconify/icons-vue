<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm26vc1og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="sm26vc1og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gender-trans-20-solid" /></template>
