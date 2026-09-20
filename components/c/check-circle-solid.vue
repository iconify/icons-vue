<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qva8gmbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qva8gmbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:check-circle-solid" /></template>
