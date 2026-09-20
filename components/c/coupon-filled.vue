<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzh_mgbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dzh_mgbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:coupon-filled" /></template>
