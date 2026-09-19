<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe2kkz7uf.css';
import '../../css/d/dbikkebwp.css';
import '../../css/m/ms5yux87p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qe2kkz7uf"/><path class="dbikkebwp"/><path class="ms5yux87p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:aftereffects" /></template>
