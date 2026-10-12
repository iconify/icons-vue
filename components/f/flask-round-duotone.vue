<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b6-u9uk-z.css';
import '../../css/p/p8q_2ebrp.css';
import '../../css/y/yu6g1gb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b6-u9uk-z"/><path class="p8q_2ebrp"/><path class="yu6g1gb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flask-round-duotone" /></template>
