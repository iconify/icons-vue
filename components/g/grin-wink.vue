<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr94xlp5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="tr94xlp5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-wink" /></template>
