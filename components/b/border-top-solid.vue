<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrqqjcbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qrqqjcbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-top-solid" /></template>
