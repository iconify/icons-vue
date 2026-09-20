<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":302};
const content = `<path class="wex_nxbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:descript-icon" /></template>
<style>
.wex_nxbgy {
  fill: var(--svg-color--f73b3b, #f73b3b);
  d: path("M0 274.127c0 16.488 10.704 27.15 27.15 27.15h79.319c47.328 0 86.044-15.994 112.333-44.047H0zM106.469 0H27.15C10.704 0 0 10.663 0 27.15v16.898h218.843C192.513 15.995 153.797 0 106.469 0m69.228 193.579c0 13.329 8.695 21.983 22.065 21.983h47.534c5.372-13.37 9.023-28.053 10.704-43.925h-58.238c-13.37 0-22.065 8.654-22.065 21.983zm-65.865-85.757c0 13.33 8.694 21.982 22.064 21.982H256c-1.681-15.871-5.29-30.554-10.704-43.924h-113.4c-13.37 0-22.064 8.654-22.064 21.983zm22.023 85.757c0-13.329-8.694-21.983-22.065-21.983H0v43.925h109.79c13.37 0 22.065-8.654 22.065-21.983zM65.99 107.822c0-13.33-8.694-21.983-22.065-21.983H0v43.925h43.924c13.37 0 22.065-8.654 22.065-21.983z");
}

</style>
