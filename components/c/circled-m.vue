<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at5new48p.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/g/gpvjwxk6r.css';
import '../../css/x/xxvql1bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle transform="translate(46.558 26.92)scale(3.04614)" class="at5new48p"/><g transform="translate(-3.216 -3.216)scale(1.09)" class="sxsjrzbyv"><path class="gpvjwxk6r"/><circle transform="translate(45.78 27.64)scale(2.795)" class="xxvql1bwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:circled-m" /></template>
