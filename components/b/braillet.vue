<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jye27acpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="jye27acpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillet" /></template>
