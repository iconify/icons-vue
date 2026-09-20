<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq2gje9ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq2gje9ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:badge-check-solid" /></template>
