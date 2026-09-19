<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chl7dpbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chl7dpbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:folder-open" /></template>
