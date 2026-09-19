<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3_7dmu3k.css';
import '../../css/y/yfz3w9lrl.css';
import '../../css/a/aec8oobvu.css';
import '../../css/o/oeljw3b-k.css';
import '../../css/q/qu5cj7ysa.css';
import '../../css/c/cpa8pz1nt.css';
import '../../css/m/mr_yc46xm.css';
import '../../css/p/phrdbcblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n3_7dmu3k"/><circle class="yfz3w9lrl"/><circle class="aec8oobvu"/><circle class="oeljw3b-k"/><circle class="qu5cj7ysa"/><circle class="cpa8pz1nt"/><circle class="mr_yc46xm"/><circle class="phrdbcblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-loader-circle" /></template>
