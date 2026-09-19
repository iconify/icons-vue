<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4z47fb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="s4z47fb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-alt" /></template>
