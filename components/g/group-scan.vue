<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6omnp7lb.css';
import '../../css/g/gmpuzqbgg.css';
import '../../css/a/arl9_odix.css';
import '../../css/v/v783iab8c.css';
import '../../css/o/ob_nbubvj.css';
import '../../css/t/tr5qnfc9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6omnp7lb"/><path class="gmpuzqbgg"/><path class="arl9_odix"/><circle class="v783iab8c"/><circle class="ob_nbubvj"/><circle class="tr5qnfc9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:group-scan" /></template>
