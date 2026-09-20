<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ise2p3bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ise2p3bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-waves-solid" /></template>
