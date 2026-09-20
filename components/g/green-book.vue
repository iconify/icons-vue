<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcorabc0l.css';
import '../../css/h/hyq88ib-w.css';
import '../../css/k/kcrxxqbkx.css';
import '../../css/g/g-vas9vud.css';
import '../../css/h/ha2s1vbvi.css';
import '../../css/a/ay8131wny.css';
import '../../css/f/fq4ztb1zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bcorabc0l"/><path class="hyq88ib-w"/><path class="kcrxxqbkx"/><path class="g-vas9vud"/><path class="ha2s1vbvi"/><circle class="ay8131wny"/><path class="fq4ztb1zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:green-book" /></template>
