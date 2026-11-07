<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-_cv6b9l.css';
import '../../css/p/pka91bn6v.css';
import '../../css/k/k3fyfebvj.css';
import '../../css/q/qcrn5ybii.css';
import '../../css/n/nwz4fbcgd.css';
import '../../css/m/m-t4jrboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n-_cv6b9l"/><path class="pka91bn6v"/><path class="k3fyfebvj"/><path class="qcrn5ybii"/><path class="nwz4fbcgd"/><path class="m-t4jrboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:hermes" /></template>
