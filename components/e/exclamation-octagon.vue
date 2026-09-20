<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb_m5_hnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb_m5_hnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:exclamation-octagon" /></template>
