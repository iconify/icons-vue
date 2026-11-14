<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e65t62b2f"/><path class="tz0rzmg9w"/><path class="j1rlhl5wz"/><path class="hmw_z-bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:graphene" /></template>
<style>
.e65t62b2f {
  d: path("m9.809 11.244l-.875-1.5A1.5 1.5 0 0 0 7.638 9H5.862a1.5 1.5 0 0 0-1.296.744l-.875 1.5a1.5 1.5 0 0 0 0 1.512l.875 1.5A1.5 1.5 0 0 0 5.862 15h1.776a1.5 1.5 0 0 0 1.296-.744l.875-1.5a1.5 1.5 0 0 0 0-1.512");
}

.hmw_z-bre {
  d: path("m20.309 11.244l-.875-1.5A1.5 1.5 0 0 0 18.138 9h-1.776a1.5 1.5 0 0 0-1.296.744l-.875 1.5a1.5 1.5 0 0 0 0 1.512l.875 1.5a1.5 1.5 0 0 0 1.296.744h1.776a1.5 1.5 0 0 0 1.296-.744l.875-1.5a1.5 1.5 0 0 0 0-1.512");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1rlhl5wz {
  d: path("m15.059 14.244l-.875-1.5A1.5 1.5 0 0 0 12.888 12h-1.776a1.5 1.5 0 0 0-1.296.744l-.875 1.5a1.5 1.5 0 0 0 0 1.512l.875 1.5a1.5 1.5 0 0 0 1.296.744h1.776a1.5 1.5 0 0 0 1.296-.744l.875-1.5a1.5 1.5 0 0 0 0-1.512");
}

.tz0rzmg9w {
  d: path("m15.059 8.244l-.875-1.5A1.5 1.5 0 0 0 12.888 6h-1.776a1.5 1.5 0 0 0-1.296.744l-.875 1.5a1.5 1.5 0 0 0 0 1.512l.875 1.5a1.5 1.5 0 0 0 1.296.744h1.776a1.5 1.5 0 0 0 1.296-.744l.875-1.5a1.5 1.5 0 0 0 0-1.512");
}

</style>
