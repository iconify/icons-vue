<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wism3vaym.css';
import '../../css/s/sp21nbblb.css';
import '../../css/s/s__9l0bok.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><path class="sp21nbblb"/><path class="s__9l0bok"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-martinique" /></template>
