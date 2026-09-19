<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8mc9p7aq.css';
import '../../css/w/wlmt3rjgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8mc9p7aq"/><path class="wlmt3rjgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image" /></template>
