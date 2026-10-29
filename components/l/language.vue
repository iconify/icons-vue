<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk_4ahm4b.css';
import '../../css/f/fvv8vzbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk_4ahm4b wm-k"/><path class="fvv8vzbvy wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:language" /></template>
