<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9ejun91r.css';
import '../../css/z/zb03b0nag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9ejun91r"/><path class="zb03b0nag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:evergreen" /></template>
