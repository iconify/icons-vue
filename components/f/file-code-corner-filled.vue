<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g61trzimo.css';
import '../../css/u/u0m-i_fxn.css';
import '../../css/k/k6ug5mbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g61trzimo"/><path class="u0m-i_fxn"/><path class="k6ug5mbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-code-corner-filled" /></template>
