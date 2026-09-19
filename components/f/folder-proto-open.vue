<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1crshb5u.css';
import '../../css/m/m7eao3b3n.css';
import '../../css/p/pdp-khgvt.css';
import '../../css/p/p--k-fr3e.css';
import '../../css/d/drjz59bdd.css';
import '../../css/l/lku96obpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h1crshb5u"/><g class="m7eao3b3n"><path transform="matrix(.5672 0 0 .62953 6.734 6.975)" class="pdp-khgvt"/><path transform="matrix(.5672 0 0 .62953 6.734 6.975)" class="p--k-fr3e"/><path transform="matrix(.5672 0 0 .62953 6.734 6.975)" class="drjz59bdd"/><path transform="matrix(.5672 0 0 .62953 6.734 6.975)" class="lku96obpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-proto-open" /></template>
