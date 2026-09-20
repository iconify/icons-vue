<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scc60hb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scc60hb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-x-sharp" /></template>
