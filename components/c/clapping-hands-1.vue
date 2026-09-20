<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozo992xml.css';
import '../../css/n/nqlzko5vk.css';
import '../../css/d/dp6zglblp.css';
import '../../css/l/lcvvitbre.css';
import '../../css/u/uh4lz_zjg.css';
import '../../css/o/o33i2kbtt.css';
import '../../css/h/hu2gv17rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ozo992xml"/><path class="nqlzko5vk"/><path class="dp6zglblp"/><path class="lcvvitbre"/><path class="uh4lz_zjg"/><path class="o33i2kbtt"/><path class="hu2gv17rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:clapping-hands-1" /></template>
