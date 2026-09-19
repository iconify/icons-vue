<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo51enbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wo51enbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:globe-alt-01-filled" /></template>
