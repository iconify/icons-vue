<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhpl1y4rb.css';
import '../../css/u/ur-5r006n.css';
import '../../css/r/r4dfx2bhp.css';
import '../../css/m/mymo3vnpd.css';
import '../../css/n/n6pfh3lzs.css';
import '../../css/l/lb80qlbob.css';
import '../../css/g/g543omyhm.css';
import '../../css/a/asn4lebbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="rhpl1y4rb"/><path class="ur-5r006n"/><path class="r4dfx2bhp"/><path class="mymo3vnpd"/><path class="n6pfh3lzs"/><g class="lb80qlbob"><path class="g543omyhm"/><path class="asn4lebbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:carrot" /></template>
