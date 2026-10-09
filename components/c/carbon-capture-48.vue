<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq4n2vb1a.css';
import '../../css/p/pwrb__blp.css';
import '../../css/i/ic_zdt4yu.css';
import '../../css/z/z3_5cgb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cq4n2vb1a"/><path class="pwrb__blp"/><path class="ic_zdt4yu"/><path class="z3_5cgb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-capture-48" /></template>
