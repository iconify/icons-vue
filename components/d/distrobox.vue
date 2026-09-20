<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at0rj4ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at0rj4ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:distrobox" /></template>
