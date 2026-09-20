<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb71i3b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb71i3b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:jump-fill" /></template>
