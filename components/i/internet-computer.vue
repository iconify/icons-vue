<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scdc82aor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scdc82aor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:internet-computer" /></template>
