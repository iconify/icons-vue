<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhms3xbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhms3xbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:jamstack" /></template>
