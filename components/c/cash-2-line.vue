<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc7lxnfds.css';
import '../../css/u/u-06obvoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc7lxnfds"/><path class="u-06obvoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cash-2-line" /></template>
