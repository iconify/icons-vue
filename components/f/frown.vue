<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbsogcciw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbsogcciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:frown" /></template>
