<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q62gep4ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q62gep4ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-network" /></template>
