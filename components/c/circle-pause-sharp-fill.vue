<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqrj2zbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqrj2zbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-pause-sharp-fill" /></template>
