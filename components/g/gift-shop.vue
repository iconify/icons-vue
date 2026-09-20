<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-ft4gl8r.css';
import '../../css/n/nn7iw1brc.css';
import '../../css/z/zackx91ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n-ft4gl8r"/><path class="nn7iw1brc"/><path class="zackx91ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:gift-shop" /></template>
