<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5bpy3h5o.css';
import '../../css/m/mcxelrguj.css';
import '../../css/c/c3wcwvbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5bpy3h5o"/><path class="mcxelrguj"/><path class="c3wcwvbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-sync-filled" /></template>
