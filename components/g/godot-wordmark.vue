<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnt2i8b5v.css';
import '../../css/p/p2p39tb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jnt2i8b5v"/><path class="p2p39tb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:godot-wordmark" /></template>
