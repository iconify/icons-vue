<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c94fvigpe.css';
import '../../css/o/o2w5jcckl.css';
import '../../css/b/b5njnqb9q.css';
import '../../css/c/cuexzmbor.css';
import '../../css/o/oxnwwcb0o.css';
import '../../css/z/zgesedcxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c94fvigpe"/><circle class="o2w5jcckl"/><path class="b5njnqb9q"/><circle class="cuexzmbor"/><circle class="oxnwwcb0o"/><circle class="zgesedcxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:eye-in-speech-bubble" /></template>
