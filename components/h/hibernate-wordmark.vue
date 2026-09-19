<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9dw0k0wu.css';
import '../../css/c/cgvt02brm.css';
import '../../css/r/rc-mzs_am.css';
import '../../css/l/lr9yqg-sj.css';
import '../../css/q/qkuzx61vw.css';
import '../../css/f/fslfzccar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p9dw0k0wu"/><path class="cgvt02brm"/><path class="rc-mzs_am"/><path class="lr9yqg-sj"/><path class="qkuzx61vw"/><path class="fslfzccar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:hibernate-wordmark" /></template>
