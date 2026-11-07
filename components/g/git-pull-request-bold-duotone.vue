<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5qboab5t.css';
import '../../css/o/oeh5lxbqa.css';
import '../../css/p/p03812bxn.css';
import '../../css/m/mnelrmb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5qboab5t"/><path clip-rule="evenodd" class="oeh5lxbqa"/><path clip-rule="evenodd" class="p03812bxn"/><path clip-rule="evenodd" class="mnelrmb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-pull-request-bold-duotone" /></template>
