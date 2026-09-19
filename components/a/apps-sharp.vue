<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovar_db6u.css';
import '../../css/o/ornud8som.css';
import '../../css/h/h50b4gb5s.css';
import '../../css/v/vf0cdobje.css';
import '../../css/d/dt4cwkb0d.css';
import '../../css/k/kzac8sb8v.css';
import '../../css/c/cz08gwbzo.css';
import '../../css/e/eb9lbnb9n.css';
import '../../css/n/n4wzhsjzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ovar_db6u"/><rect class="ornud8som"/><rect class="h50b4gb5s"/><rect class="vf0cdobje"/><rect class="dt4cwkb0d"/><rect class="kzac8sb8v"/><rect class="cz08gwbzo"/><rect class="eb9lbnb9n"/><rect class="n4wzhsjzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:apps-sharp" /></template>
