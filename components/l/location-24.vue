<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlz_osbhr.css';
import '../../css/r/rwwu0mw7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlz_osbhr"/><path class="rwwu0mw7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:location-24" /></template>
