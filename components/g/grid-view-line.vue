<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7e3rdlae.css';
import '../../css/o/ovl5-ob0m.css';
import '../../css/a/a_-zu1dnz.css';
import '../../css/h/htaep2cnf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 h7e3rdlae"/><path class="clr-i-outline clr-i-outline-path-2 ovl5-ob0m"/><path class="a_-zu1dnz clr-i-outline clr-i-outline-path-3"/><path class="clr-i-outline clr-i-outline-path-4 htaep2cnf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:grid-view-line" /></template>
