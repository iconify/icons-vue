<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0ltb5bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ltb5bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:google-drive" /></template>
