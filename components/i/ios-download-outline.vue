<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eie4uo28e.css';
import '../../css/g/gn89h9b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eie4uo28e"/><path class="gn89h9b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-download-outline" /></template>
