<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drr_rdr2u.css';
import '../../css/j/jw6etd-fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drr_rdr2u"/><path class="jw6etd-fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:chart-pie-solid" /></template>
