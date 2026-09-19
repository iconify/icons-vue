<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsid5zbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsid5zbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clipboard-minus-filled" /></template>
