<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pssi10jzr.css';
import '../../css/g/gnsad6zcg.css';
import '../../css/e/enwgdw7qx.css';
import '../../css/u/urugr0b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pssi10jzr"/><path class="gnsad6zcg"/><path class="enwgdw7qx"/><path class="urugr0b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:clojure" /></template>
