<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv2isybhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":640};
const content = `<path class="gv2isybhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:image" /></template>
