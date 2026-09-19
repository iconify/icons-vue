<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_4euzb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m_4euzb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:clock-small-filled" /></template>
