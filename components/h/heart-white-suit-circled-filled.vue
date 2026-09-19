<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hypj4bcrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hypj4bcrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-white-suit-circled-filled" /></template>
