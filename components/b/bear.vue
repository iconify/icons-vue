<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0vz-tbdb.css';
import '../../css/h/h5q9tn6hy.css';
import '../../css/r/riktqubqo.css';
import '../../css/z/zrbvzsbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0vz-tbdb"/><path class="h5q9tn6hy"/><path class="riktqubqo"/><path class="zrbvzsbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bear" /></template>
