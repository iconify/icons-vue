<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wstt5lble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wstt5lble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-stop-userprogram" /></template>
