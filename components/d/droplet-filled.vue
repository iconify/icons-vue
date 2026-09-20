<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhup8hb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhup8hb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-filled" /></template>
