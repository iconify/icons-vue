<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8cb8db6z.css';
import '../../css/o/ob_nbubvj.css';
import '../../css/n/n3usjxbmr.css';
import '../../css/l/lp1s2ud1e.css';
import '../../css/s/st7hb1-ec.css';
import '../../css/j/jw--fn29d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="z8cb8db6z"/><circle class="ob_nbubvj"/><circle class="n3usjxbmr"/><circle class="lp1s2ud1e"/><circle class="st7hb1-ec"/><path class="jw--fn29d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:color-palette" /></template>
