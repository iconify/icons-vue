<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-2ra_b2r.css';
import '../../css/s/sjfm5_b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-2ra_b2r"/><path class="sjfm5_b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:inbox-fill" /></template>
