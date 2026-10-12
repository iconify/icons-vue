<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z7ld48b8v.css';
import '../../css/t/tst6sfblt.css';
import '../../css/c/cofp1obby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z7ld48b8v"/><path class="tst6sfblt"/><path class="cofp1obby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:glasses-duotone" /></template>
