<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nab6klb5t.css';
import '../../css/b/bdbr-nauf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nab6klb5t"/><path class="bdbr-nauf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:google" /></template>
