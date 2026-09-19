<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e0almzhrq"/><path class="tsx6rob9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:hollow-red-circle" /></template>
<style>
.e0almzhrq {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("M31.915 0C14.323 0 .008 14.317.008 31.909c0 17.593 14.315 31.909 31.907 31.909c17.595 0 31.911-14.315 31.911-31.909C63.826 14.317 49.51 0 31.915 0m0 55.908c-13.232 0-23.998-10.766-23.998-24s10.766-24 23.998-24c13.236 0 24 10.767 24 24c0 13.235-10.766 24-24 24");
}

.tsx6rob9x {
  fill: var(--svg-color--8b182c, #8b182c);
  d: path("M4.696 31.909C4.696 15.107 17.756 1.33 34.258.12C33.478.063 32.701 0 31.909 0C14.313 0 0 14.317 0 31.909c0 17.593 14.313 31.909 31.909 31.909c.792 0 1.569-.063 2.349-.12c-16.5-1.211-29.562-14.988-29.562-31.789m29.564 23.88c.772.076 1.555.119 2.347.119c13.234 0 24-10.766 24-24s-10.766-24-24-24c-.792 0-1.574.043-2.347.12c12.134 1.184 21.65 11.44 21.65 23.882s-9.516 22.696-21.65 23.881");
}

</style>
