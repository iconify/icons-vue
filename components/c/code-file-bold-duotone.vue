<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgd8bzbml.css';
import '../../css/w/wa67eqk3b.css';
import '../../css/l/lqdbwbc4f.css';
import '../../css/r/r-s7r2hkm.css';
import '../../css/k/kn13bqbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="wa67eqk3b"/><path class="lqdbwbc4f"/><path class="r-s7r2hkm"/><path class="kn13bqbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-file-bold-duotone" /></template>
