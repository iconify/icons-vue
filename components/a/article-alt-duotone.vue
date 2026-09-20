<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfyooabog.css';
import '../../css/g/gxd-8e_9n.css';
import '../../css/m/mjkpimbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfyooabog"/><path class="gxd-8e_9n"/><path class="mjkpimbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-alt-duotone" /></template>
