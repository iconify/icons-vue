<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1xy6nh9u.css';
import '../../css/b/b74ikwezj.css';
import '../../css/d/dq12o7ykb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n1xy6nh9u"/><circle class="b74ikwezj"/><circle class="dq12o7ykb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:ellipsis-h" /></template>
