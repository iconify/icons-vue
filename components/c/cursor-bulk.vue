<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9cm9pbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-bulk" /></template>
<style>
.d9cm9pbbm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.316 5.051l6 2c.392.131.754.338 1.066.609c.584.506 1.041 1.28.917 2.077c-.078.503-.398.93-.852 1.157l-2 1c-.236.119-.473.301-.599.54l2.859 2.859a2.414 2.414 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0l-2.859-2.859c-.239.126-.421.363-.54.599l-1 2a1.56 1.56 0 0 1-1.157.852c-.797.124-1.571-.333-2.077-.917a3.2 3.2 0 0 1-.609-1.066l-4-12a2.582 2.582 0 0 1 3.265-3.265Z");
}

</style>
