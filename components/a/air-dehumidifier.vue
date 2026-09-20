<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbk7ft81q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbk7ft81q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:air-dehumidifier" /></template>
