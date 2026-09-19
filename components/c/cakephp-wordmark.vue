<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwd-a5bvw.css';
import '../../css/d/dz-ia743r.css';
import '../../css/q/qd99e1bmu.css';
import '../../css/t/tri7xd97g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cwd-a5bvw"/><path class="dz-ia743r"/><path class="qd99e1bmu"/><path class="tri7xd97g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cakephp-wordmark" /></template>
