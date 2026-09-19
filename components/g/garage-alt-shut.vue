<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr_tvqbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr_tvqbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:garage-alt-shut" /></template>
