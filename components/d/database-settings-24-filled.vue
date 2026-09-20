<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6m_u5b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:database-settings-24-filled" /></template>
<style>
.k6m_u5b9w {
  fill: currentColor;
  d: path("M16.06 12.901a2 2 0 0 0 2.9.001l.493-.518a5.3 5.3 0 0 1 1.485.922l-.187.63a2 2 0 0 0 1.45 2.511l.54.13a5.7 5.7 0 0 1 .005 1.807l-.584.144a2 2 0 0 0-1.44 2.496l.197.687a5.3 5.3 0 0 1-1.483.912l-.498-.524a2 2 0 0 0-2.899 0l-.493.518a5.3 5.3 0 0 1-1.484-.922l.186-.63a2 2 0 0 0-1.45-2.511l-.54-.13a5.7 5.7 0 0 1-.006-1.808l.584-.144a2 2 0 0 0 1.441-2.496l-.198-.686c.44-.382.94-.693 1.483-.913zM4 9.054c.502.45 1.084.822 1.672 1.116c1.697.848 3.936 1.33 6.328 1.33a16.7 16.7 0 0 0 3.22-.307c-2.465.991-4.22 3.52-4.22 6.307c0 1.737.682 3.314 1.792 4.48q-.39.019-.792.02c-4.418 0-8-1.79-8-4zM17.499 16c-.8 0-1.449.672-1.45 1.5S16.7 19 17.5 19s1.45-.672 1.45-1.5S18.3 16 17.5 16M12 2c4.418 0 8 1.79 8 4s-3.582 4-8 4s-8-1.79-8-4s3.582-4 8-4");
}

</style>
