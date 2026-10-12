<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pydxmub-s.css';
import '../../css/s/sru-zac9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pydxmub-s"/><path class="sru-zac9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:history-fill-20" /></template>
