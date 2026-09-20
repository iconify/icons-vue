<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a8m08gb9a.css';
import '../../css/e/e_6znci3x.css';
import '../../css/g/gbtkpcbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a8m08gb9a"/><path class="e_6znci3x"/><path class="gbtkpcbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:bug-flat" /></template>
