<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4ilpsblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4ilpsblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:check-24" /></template>
