<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dur0b2p3t.css';
import '../../css/e/enn-20bck.css';
import '../../css/g/grdy41zrz.css';
import '../../css/e/e47-m7bik.css';
import '../../css/m/m18c_8b9n.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="enn-20bck"/><path class="grdy41zrz"/><circle class="e47-m7bik"/><path class="m18c_8b9n"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-spain" /></template>
