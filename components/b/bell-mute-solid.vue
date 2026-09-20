<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsrjsjbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsrjsjbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bell-mute-solid" /></template>
