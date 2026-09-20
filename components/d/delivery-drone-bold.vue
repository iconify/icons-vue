<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uim7w5btd.css';
import '../../css/q/qvdt6db7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uim7w5btd"/><path class="qvdt6db7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:delivery-drone-bold" /></template>
