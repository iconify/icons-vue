<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw3gh1bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gw3gh1bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:discord-outline" /></template>
