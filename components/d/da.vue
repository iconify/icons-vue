<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/u/u_rm_9byk.css';
import '../../css/z/zt6pghb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsDa0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsDa0)"><path class="u_rm_9byk"/><path class="zt6pghb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:da" /></template>
