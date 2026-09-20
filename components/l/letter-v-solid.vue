<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p51e5geti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p51e5geti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-v-solid" /></template>
