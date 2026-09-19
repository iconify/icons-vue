<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdhrlnphl.css';
import '../../css/d/drbu3zb8y.css';
import '../../css/m/mol134btx.css';
import '../../css/t/t5hp_obfp.css';
import '../../css/k/k36i95p_h.css';
import '../../css/p/pjnb8bc5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pdhrlnphl"/><path class="drbu3zb8y"/><path class="mol134btx"/><path clip-rule="evenodd" class="t5hp_obfp"/><path clip-rule="evenodd" class="k36i95p_h"/><path class="pjnb8bc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:huggingface-wordmark" /></template>
