<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k889x9ems.css';
import '../../css/h/h9m_z6b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k889x9ems"/><path class="h9m_z6b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:badge-verified" /></template>
