<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6cvwtbsp.css';
import '../../css/m/mi7mcubng.css';
import '../../css/w/wu28wrb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d6cvwtbsp"/><path class="mi7mcubng"/><path class="wu28wrb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:library-48-bold" /></template>
