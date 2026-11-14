<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lere1oclx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hair-bow" /></template>
<style>
.lere1oclx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.903 17.633l5.281-3.361q.669.478 1.816.478t1.816-.478l5.281 3.361l.017.01q1.1.66 2.114.119Q22.25 17.217 22.25 16V8q0-1.217-1.022-1.762q-1.014-.541-2.114.119l-.017.01l-5.281 3.361Q13.147 9.25 12 9.25t-1.816.478L4.903 6.367l-.017-.01q-1.1-.66-2.114-.119Q1.75 6.783 1.75 8v8q0 1.217 1.022 1.762q1.014.541 2.114-.119zm-.796-9.994l5.259 3.347Q9.25 11.435 9.25 12t.116 1.014l-5.259 3.347q-.367.217-.629.077q-.228-.121-.228-.438V8q0-.317.228-.438q.262-.14.629.077m15.786 8.722l-5.259-3.347q.116-.449.116-1.014t-.116-1.014l5.259-3.347q.367-.217.629-.077q.228.121.228.438v8q0 .317-.228.438q-.262.14-.629-.077");
}

</style>
