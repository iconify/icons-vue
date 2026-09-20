<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag15_abea.css';
import '../../css/k/k3jegzb8r.css';
import '../../css/b/b0zjanbgx.css';
import '../../css/x/xqk69l56d.css';
import '../../css/d/d2z4wyw-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":92.3,"height":132.3};
const content = `<path class="ag15_abea"/><path class="k3jegzb8r"/><path class="b0zjanbgx"/><path class="xqk69l56d"/><path class="d2z4wyw-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-maps" /></template>
