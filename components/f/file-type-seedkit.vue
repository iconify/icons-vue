<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ygoyaacxx"/><path class="x3mqhubha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-seedkit" /></template>
<style>
.x3mqhubha {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.56 16.922c0-.214.174-.387.388-.387H21.6a5.036 5.036 0 0 1 5.04 5.03c0 2.78-2.256 5.032-5.04 5.032s-5.04-2.253-5.04-5.031zm0-1.893c0 .214.174.387.388.387H21.6a5.036 5.036 0 0 0 5.04-5.03c0-2.78-2.256-5.032-5.04-5.032s-5.04 2.253-5.04 5.031zm-1.12 1.893a.39.39 0 0 0-.388-.387H10.4a5.036 5.036 0 0 0-5.04 5.03a5.036 5.036 0 0 0 5.04 5.032a5.036 5.036 0 0 0 5.04-5.031zm0-1.893a.39.39 0 0 1-.388.387H10.4a5.036 5.036 0 0 1-5.04-5.03a5.036 5.036 0 0 1 5.04-5.032a5.036 5.036 0 0 1 5.04 5.031z");
}

.ygoyaacxx {
  fill: var(--svg-color--4f51e5, #4f51e5);
  d: path("M2 10.944c0-3.13 0-4.696.61-5.892a5.6 5.6 0 0 1 2.448-2.443c1.198-.61 2.766-.61 5.902-.61h10.08c3.136 0 4.704 0 5.902.61a5.6 5.6 0 0 1 2.448 2.443c.61 1.196.61 2.761.61 5.892v10.062c0 3.13 0 4.696-.61 5.892a5.6 5.6 0 0 1-2.448 2.443c-1.198.61-2.766.61-5.902.61H10.96c-3.136 0-4.704 0-5.902-.61a5.6 5.6 0 0 1-2.448-2.443C2 25.702 2 24.137 2 21.006z");
}

</style>
