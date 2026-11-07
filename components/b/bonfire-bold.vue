<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1ntc_v_g.css';
import '../../css/y/yc8urfbgx.css';
import '../../css/j/jgzaczl_g.css';
import '../../css/b/bt-e1yb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1ntc_v_g"/><path class="yc8urfbgx"/><path class="jgzaczl_g"/><path clip-rule="evenodd" class="bt-e1yb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bonfire-bold" /></template>
