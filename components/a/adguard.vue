<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9_19ptk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li9_19ptk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adguard" /></template>
