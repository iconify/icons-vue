<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ouamk3z.css';
import '../../css/o/o5o821fyy.css';
import '../../css/u/uz6l94i4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="n9ouamk3z"/><path class="o5o821fyy"/><path class="uz6l94i4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:instagram-fill" /></template>
