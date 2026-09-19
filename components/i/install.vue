<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/w006b1bic.css';
import '../../css/u/u-r8ydben.css';
import '../../css/o/o-4xw7lai.css';
import '../../css/v/vtw6jyqmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="w006b1bic"/><path class="u-r8ydben"/><path class="o-4xw7lai"/><path class="vtw6jyqmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:install" /></template>
