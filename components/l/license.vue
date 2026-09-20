<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syfbt_k0c.css';
import '../../css/x/xemxelb-k.css';
import '../../css/i/iqucf9blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="syfbt_k0c"/><path class="xemxelb-k"/><path class="iqucf9blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:license" /></template>
