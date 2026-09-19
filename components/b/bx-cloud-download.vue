<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se_exubjd.css';
import '../../css/c/cdr84abnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se_exubjd"/><path class="cdr84abnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cloud-download" /></template>
