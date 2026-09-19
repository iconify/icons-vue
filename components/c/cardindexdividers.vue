<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbhakgbzs.css';
import '../../css/o/oja5rwz9i.css';
import '../../css/l/l36n89b8l.css';
import '../../css/u/u9th8bbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rbhakgbzs"/><path class="oja5rwz9i"/><path class="l36n89b8l"/><path class="u9th8bbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cardindexdividers" /></template>
