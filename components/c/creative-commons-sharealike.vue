<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvyl42ogw.css';
import '../../css/l/l252cwxrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mvyl42ogw"/><path class="l252cwxrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:creative-commons-sharealike" /></template>
