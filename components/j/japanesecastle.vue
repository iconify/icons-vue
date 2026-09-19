<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e906i-3ln.css';
import '../../css/i/i6zfmwblj.css';
import '../../css/k/kod42bcng.css';
import '../../css/p/pv2s4tb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e906i-3ln"/><path class="i6zfmwblj"/><path class="kod42bcng"/><path class="pv2s4tb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:japanesecastle" /></template>
