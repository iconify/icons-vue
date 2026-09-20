<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smvzpprvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smvzpprvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:delete-on-filled" /></template>
