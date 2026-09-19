<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzfrs0mvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zzfrs0mvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:desktop-computer" /></template>
