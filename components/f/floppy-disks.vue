<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/coxf6bb6r.css';
import '../../css/b/b7cp9xema.css';
import '../../css/z/z0tdu3owt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="coxf6bb6r"/><path class="b7cp9xema"/><path class="z0tdu3owt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:floppy-disks" /></template>
