<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrd3ofbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrd3ofbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrange-by-letters-a-z" /></template>
