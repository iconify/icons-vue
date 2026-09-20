<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrasw9bbm.css';
import '../../css/i/in5wtwq8h.css';
import '../../css/l/lgruf5j3n.css';
import '../../css/e/e4zfowz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="wrasw9bbm"/><path class="in5wtwq8h"/><path class="lgruf5j3n"/><path class="e4zfowz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:a-button-blood-type" /></template>
