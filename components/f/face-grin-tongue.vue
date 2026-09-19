<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfnl83bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfnl83bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-tongue" /></template>
