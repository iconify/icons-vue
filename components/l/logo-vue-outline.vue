<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exv3ojb0v.css';
import '../../css/s/sdocp_b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="exv3ojb0v"/><path class="sdocp_b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-vue-outline" /></template>
